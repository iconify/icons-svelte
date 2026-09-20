<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/o/odwtxx.css';
import '../../css/e/efzwqq.css';
import '../../css/s/so-from-8.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew odwtxx"/><path class="efzwqq iw1iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:computer-filled" {...props}></Icon>
