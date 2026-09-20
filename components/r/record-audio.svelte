<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a15vrjyzh.css';
import '../../css/f/fwgabzb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="a15vrjyzh"/><path class="fwgabzb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:record-audio" {...props}></Icon>
