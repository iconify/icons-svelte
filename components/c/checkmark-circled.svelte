<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj6el_b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rj6el_b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:checkmark-circled" {...props}></Icon>
