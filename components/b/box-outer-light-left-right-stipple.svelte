<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx8ai4b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="zx8ai4b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-left-right-stipple" {...props}></Icon>
