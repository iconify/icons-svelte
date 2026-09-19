<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boz_p5b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="boz_p5b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:remote" {...props}></Icon>
