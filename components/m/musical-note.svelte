<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gstd5dbik.css';
import '../../css/j/j4hy2kb8r.css';
import '../../css/z/zn0v0yjgo.css';
import '../../css/a/axli2ab7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gstd5dbik"/><path class="j4hy2kb8r"/><path class="zn0v0yjgo"/><path class="axli2ab7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:musical-note" {...props}></Icon>
