<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgyx6_bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="xgyx6_bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:angle-double-up" {...props}></Icon>
