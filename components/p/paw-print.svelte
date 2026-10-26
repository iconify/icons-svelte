<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zttyezb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zttyezb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:paw-print" {...props}></Icon>
