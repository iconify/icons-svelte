<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9inqtbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="z9inqtbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:pagelines" {...props}></Icon>
