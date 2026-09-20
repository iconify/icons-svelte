<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3inu9bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t3inu9bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-thin-up" {...props}></Icon>
