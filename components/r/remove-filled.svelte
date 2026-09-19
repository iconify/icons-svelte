<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl_u86lbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pl_u86lbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:remove-filled" {...props}></Icon>
