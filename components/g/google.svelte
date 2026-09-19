<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eftaeeh0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eftaeeh0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:google" {...props}></Icon>
