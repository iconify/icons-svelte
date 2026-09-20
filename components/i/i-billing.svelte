<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkps9h2bk.css';
import '../../css/q/q40219bwz.css';
import '../../css/r/rqyk8bb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hkps9h2bk"/><path class="q40219bwz"/><path class="rqyk8bb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-billing" {...props}></Icon>
