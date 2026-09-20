<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqzo2e_ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqzo2e_ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fossa" {...props}></Icon>
