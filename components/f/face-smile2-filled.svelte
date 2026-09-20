<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbr5azbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbr5azbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:face-smile2-filled" {...props}></Icon>
