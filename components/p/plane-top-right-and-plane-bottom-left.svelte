<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6_kpfbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k6_kpfbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-top-right-and-plane-bottom-left" {...props}></Icon>
