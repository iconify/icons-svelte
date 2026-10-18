<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv0sx3-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv0sx3-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-horizontal-justify-start" {...props}></Icon>
