<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgy3tobaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bgy3tobaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:moon" {...props}></Icon>
