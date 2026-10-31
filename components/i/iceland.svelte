<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob20kwbzk.css';
import '../../css/l/l1kbw1b1l.css';
import '../../css/x/x0hxdhfls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ob20kwbzk"/><path class="l1kbw1b1l"/><path class="x0hxdhfls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:iceland" {...props}></Icon>
