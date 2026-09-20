<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd07yqmly.css';
import '../../css/z/zlrwl1bnk.css';
import '../../css/l/lstaoj3fp.css';
import '../../css/i/i7sr6ubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd07yqmly"/><path class="zlrwl1bnk"/><path class="lstaoj3fp"/><path class="i7sr6ubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:hockey-mask" {...props}></Icon>
