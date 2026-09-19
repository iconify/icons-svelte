<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzafr3b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="rzafr3b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:creative-commons-pd-alt" {...props}></Icon>
