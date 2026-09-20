<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuzaj4bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zuzaj4bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:red-hat-lightspeed-dark" {...props}></Icon>
