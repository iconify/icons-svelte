<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5fxqqbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5fxqqbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-alert" {...props}></Icon>
