<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8_l-zb6q.css';
import '../../css/v/v0ztzdxtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8_l-zb6q"/><path class="v0ztzdxtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-dog" {...props}></Icon>
