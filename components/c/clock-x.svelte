<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2t86ck2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2t86ck2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clock-x" {...props}></Icon>
