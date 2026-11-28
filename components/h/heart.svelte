<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zel29wb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zel29wb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart" {...props}></Icon>
