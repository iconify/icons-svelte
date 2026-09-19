<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7bae4kho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f7bae4kho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bell" {...props}></Icon>
