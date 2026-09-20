<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wak7u4bkm.css';
import '../../css/u/uybk_4bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wak7u4bkm"/><path class="uybk_4bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:figma-line" {...props}></Icon>
