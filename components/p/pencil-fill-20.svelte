<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdqfj0vsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rdqfj0vsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-fill-20" {...props}></Icon>
