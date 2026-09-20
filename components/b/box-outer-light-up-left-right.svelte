<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz98gcbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xz98gcbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-left-right" {...props}></Icon>
