<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4mtfqb_h.css';
import '../../css/r/racdv353u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4mtfqb_h"/><path class="racdv353u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:guitar-filled" {...props}></Icon>
