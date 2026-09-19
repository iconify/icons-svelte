<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj3z_faaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="wj3z_faaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:megaport" {...props}></Icon>
