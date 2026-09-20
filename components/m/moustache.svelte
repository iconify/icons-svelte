<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exl5b4b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="exl5b4b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:moustache" {...props}></Icon>
