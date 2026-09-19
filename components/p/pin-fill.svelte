<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t413ssb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="t413ssb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pin-fill" {...props}></Icon>
