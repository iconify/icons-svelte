<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vucvnjbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vucvnjbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pswap" {...props}></Icon>
