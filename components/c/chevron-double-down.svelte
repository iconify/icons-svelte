<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdout_b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fdout_b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chevron-double-down" {...props}></Icon>
