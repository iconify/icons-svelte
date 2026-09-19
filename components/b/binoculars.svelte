<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy-xt_bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy-xt_bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:binoculars" {...props}></Icon>
