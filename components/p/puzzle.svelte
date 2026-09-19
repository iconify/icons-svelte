<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prxmtjbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prxmtjbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:puzzle" {...props}></Icon>
