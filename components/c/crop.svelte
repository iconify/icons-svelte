<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_uz53-xm.css';
import '../../css/g/g_a2zwbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l_uz53-xm"/><path class="g_a2zwbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:crop" {...props}></Icon>
