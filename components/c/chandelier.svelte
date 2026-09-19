<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pil6s8bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pil6s8bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chandelier" {...props}></Icon>
