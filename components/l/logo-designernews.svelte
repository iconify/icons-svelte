<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8p4fabkp.css';
import '../../css/d/d_g8hik9b.css';
import '../../css/d/d4yobybuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8p4fabkp"/><path class="d_g8hik9b"/><path class="d4yobybuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-designernews" {...props}></Icon>
