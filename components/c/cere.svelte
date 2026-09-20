<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5zexkbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5zexkbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cere" {...props}></Icon>
