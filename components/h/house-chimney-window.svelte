<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvz41nqkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="wvz41nqkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-chimney-window" {...props}></Icon>
