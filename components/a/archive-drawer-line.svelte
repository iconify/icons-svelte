<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg53enbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg53enbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:archive-drawer-line" {...props}></Icon>
