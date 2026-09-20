<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yki9d0bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yki9d0bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-up-left-right" {...props}></Icon>
