<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga-2uf8mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ga-2uf8mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:creative-commons" {...props}></Icon>
