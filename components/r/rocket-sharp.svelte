<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmiv43pty.css';
import '../../css/z/zpbo7acvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmiv43pty"/><path class="zpbo7acvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:rocket-sharp" {...props}></Icon>
