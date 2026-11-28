<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a55fheeyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a55fheeyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heading" {...props}></Icon>
