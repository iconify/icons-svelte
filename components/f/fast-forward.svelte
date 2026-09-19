<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjbibb21a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qjbibb21a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:fast-forward" {...props}></Icon>
