<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht3kc_b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ht3kc_b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:admin" {...props}></Icon>
