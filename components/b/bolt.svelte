<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdbru3nfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1664};
const content = `<path class="tdbru3nfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bolt" {...props}></Icon>
