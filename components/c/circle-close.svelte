<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leeazsipl.css';
import '../../css/h/hmk826btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="leeazsipl"/><path class="hmk826btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:circle-close" {...props}></Icon>
