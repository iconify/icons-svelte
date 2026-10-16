<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qokjj-kmj.css';
import '../../css/a/a8vsq7owx.css';
import '../../css/p/pu0j68bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qokjj-kmj"/><path class="a8vsq7owx"/><path class="pu0j68bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-pitch-20-bold" {...props}></Icon>
