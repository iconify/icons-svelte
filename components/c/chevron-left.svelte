<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1dfrij3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="y1dfrij3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:chevron-left" {...props}></Icon>
