<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrkr6bc-w.css';
import '../../css/x/x05r09_kp.css';
import '../../css/z/zmroq2b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xrkr6bc-w"/><path class="x05r09_kp"/><path class="zmroq2b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paint-bucket-48" {...props}></Icon>
