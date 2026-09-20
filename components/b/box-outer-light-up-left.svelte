<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yachl4bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yachl4bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-left" {...props}></Icon>
