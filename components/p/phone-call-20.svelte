<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz7zambhg.css';
import '../../css/y/yt3jrachk.css';
import '../../css/q/qzi560ajg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tz7zambhg"/><path class="yt3jrachk"/><path class="qzi560ajg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-call-20" {...props}></Icon>
