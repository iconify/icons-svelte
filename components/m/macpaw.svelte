<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf_g5ibkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_g5ibkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:macpaw" {...props}></Icon>
