<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v96ik30ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="v96ik30ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-down-vertical-stipple" {...props}></Icon>
