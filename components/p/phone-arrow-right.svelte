<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz8krcb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xz8krcb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-arrow-right" {...props}></Icon>
