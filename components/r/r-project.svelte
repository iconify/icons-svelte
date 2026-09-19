<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7mdj_t3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":581,"height":512};
const content = `<path class="l7mdj_t3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:r-project" {...props}></Icon>
