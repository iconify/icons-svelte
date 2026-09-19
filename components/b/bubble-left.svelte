<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umb5xvgbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="umb5xvgbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bubble-left" {...props}></Icon>
