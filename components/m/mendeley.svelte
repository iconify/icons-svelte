<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akoiqbjnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="akoiqbjnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:mendeley" {...props}></Icon>
