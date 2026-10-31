<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdhad0ihx.css';
import '../../css/b/bjhb_puya.css';
import '../../css/w/w4m-jwb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="qdhad0ihx"/><path class="bjhb_puya"/><path class="w4m-jwb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:guinea" {...props}></Icon>
