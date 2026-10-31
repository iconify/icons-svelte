<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_uxf-nhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_uxf-nhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:contrast-round" {...props}></Icon>
