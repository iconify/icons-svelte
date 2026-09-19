<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6u7tw-2d.css';
import '../../css/b/by38gccqr.css';
import '../../css/y/y_-z-8r0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b j6u7tw-2d"/><path class="b by38gccqr"/><path class="b y_-z-8r0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-alt" {...props}></Icon>
