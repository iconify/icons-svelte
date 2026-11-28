<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgrv5ryss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgrv5ryss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:qr-code-search" {...props}></Icon>
