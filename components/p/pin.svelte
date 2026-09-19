<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq7niqbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq7niqbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:pin" {...props}></Icon>
