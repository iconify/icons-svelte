<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uymz8obqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uymz8obqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package-variant-closed-subtract" {...props}></Icon>
