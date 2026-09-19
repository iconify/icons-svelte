<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7__hwxfb.css';
import '../../css/f/fo40zs72w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u7__hwxfb"/><path class="fo40zs72w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-check" {...props}></Icon>
