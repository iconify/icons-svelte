<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qst0molkh.css';
import '../../css/f/fel1l29cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qst0molkh"/><path clip-rule="evenodd" class="fel1l29cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-hangup-16" {...props}></Icon>
