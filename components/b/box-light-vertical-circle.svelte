<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhevx-b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lhevx-b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-circle" {...props}></Icon>
