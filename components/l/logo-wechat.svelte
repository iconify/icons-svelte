<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj3gltbbh.css';
import '../../css/g/gvjt3ybox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cj3gltbbh"/><path class="gvjt3ybox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-wechat" {...props}></Icon>
