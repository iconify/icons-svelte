<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv_0-ekbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="uv_0-ekbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloudaltsync" {...props}></Icon>
