<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvg3fbb0b.css';
import '../../css/l/l7hgfejkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bvg3fbb0b"/><path class="l7hgfejkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reply-48-bold" {...props}></Icon>
