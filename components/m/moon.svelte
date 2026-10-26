<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb44_r7uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lb44_r7uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:moon" {...props}></Icon>
