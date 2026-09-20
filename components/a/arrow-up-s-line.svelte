<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmkm7dbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmkm7dbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-s-line" {...props}></Icon>
