<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks8-j5qct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks8-j5qct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-user-check" {...props}></Icon>
