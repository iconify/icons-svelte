<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exnrwkbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exnrwkbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:quick-reply" {...props}></Icon>
