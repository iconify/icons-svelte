<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-7g8hbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-7g8hbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:music-2-fill" {...props}></Icon>
