<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn2j6ebje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn2j6ebje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-5-fill" {...props}></Icon>
