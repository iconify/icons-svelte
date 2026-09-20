<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t26f_urlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t26f_urlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-from-wide-rectangle-outline" {...props}></Icon>
