<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up7s9rbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up7s9rbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-4-line" {...props}></Icon>
