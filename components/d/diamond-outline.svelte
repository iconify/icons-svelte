<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfeaq_g8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xfeaq_g8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:diamond-outline" {...props}></Icon>
