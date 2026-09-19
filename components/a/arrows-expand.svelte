<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxhq8sj5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zxhq8sj5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrows-expand" {...props}></Icon>
