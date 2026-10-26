<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz07ytgpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":35};
const content = `<path class="sz07ytgpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:oddinpay" {...props}></Icon>
