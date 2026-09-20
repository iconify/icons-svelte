<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql2ho69vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ql2ho69vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:paragraph-6" {...props}></Icon>
