<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnbgkub4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qnbgkub4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:brightness-down" {...props}></Icon>
