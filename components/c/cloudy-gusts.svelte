<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1tp2t4qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":24};
const content = `<path class="x1tp2t4qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cloudy-gusts" {...props}></Icon>
