<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr0_ucrte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gr0_ucrte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:apper" {...props}></Icon>
