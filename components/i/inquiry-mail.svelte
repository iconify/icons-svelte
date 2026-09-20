<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unc3p6dyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unc3p6dyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:inquiry-mail" {...props}></Icon>
