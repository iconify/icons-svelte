<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3j-h9wtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="q3j-h9wtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple-up-right" {...props}></Icon>
