<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hknxp1bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hknxp1bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bitcoin-sv" {...props}></Icon>
