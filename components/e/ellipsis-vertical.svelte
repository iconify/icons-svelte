<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccbo3n_4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ccbo3n_4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:ellipsis-vertical" {...props}></Icon>
