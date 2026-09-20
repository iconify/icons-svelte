<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk858wbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk858wbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:directions" {...props}></Icon>
