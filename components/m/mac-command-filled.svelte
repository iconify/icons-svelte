<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to8dx_b8t.css';
import '../../css/x/x0n0x1bdz.css';
import '../../css/f/f_lfe3b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="to8dx_b8t"/><path class="x0n0x1bdz"/><path class="f_lfe3b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:mac-command-filled" {...props}></Icon>
