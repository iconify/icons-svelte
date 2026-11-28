<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqs_mfb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqs_mfb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:diamond-solid" {...props}></Icon>
