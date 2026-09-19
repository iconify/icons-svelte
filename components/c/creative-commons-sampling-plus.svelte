<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjtk3-bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="wjtk3-bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:creative-commons-sampling-plus" {...props}></Icon>
