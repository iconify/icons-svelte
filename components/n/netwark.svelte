<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovp1n-bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ovp1n-bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:netwark" {...props}></Icon>
