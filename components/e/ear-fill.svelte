<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la_o4hbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="la_o4hbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ear-fill" {...props}></Icon>
