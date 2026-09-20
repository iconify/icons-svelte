<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3z_4ymzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t3z_4ymzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bimobject" {...props}></Icon>
