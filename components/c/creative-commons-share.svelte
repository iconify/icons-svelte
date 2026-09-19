<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr6b--b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="sr6b--b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:creative-commons-share" {...props}></Icon>
