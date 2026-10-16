<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx6vej9mh.css';
import '../../css/q/qjh6c2bbs.css';
import '../../css/x/xhkmldn9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rx6vej9mh"/><path class="qjh6c2bbs"/><path class="xhkmldn9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lockout-20" {...props}></Icon>
