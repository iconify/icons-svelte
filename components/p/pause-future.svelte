<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llwq-7b3r.css';
import '../../css/u/uufe-4b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="llwq-7b3r"/><path class="uufe-4b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pause-future" {...props}></Icon>
