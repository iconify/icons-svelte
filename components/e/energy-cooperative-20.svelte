<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khhnz4-5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="khhnz4-5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-cooperative-20" {...props}></Icon>
