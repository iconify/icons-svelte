<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2-khbbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="q2-khbbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-down-left-stipple-outer" {...props}></Icon>
