<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoy5q4b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zoy5q4b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:folder-plus" {...props}></Icon>
