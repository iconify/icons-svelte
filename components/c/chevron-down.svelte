<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsj5vxb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dsj5vxb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chevron-down" {...props}></Icon>
