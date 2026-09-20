<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuf0ygbfo.css';
import '../../css/d/d5tm45bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vuf0ygbfo"/><path class="d5tm45bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-database" {...props}></Icon>
