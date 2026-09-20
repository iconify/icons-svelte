<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qasjs_bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qasjs_bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-finger-2-line" {...props}></Icon>
