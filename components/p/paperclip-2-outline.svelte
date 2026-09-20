<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ths0tvdky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ths0tvdky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-2-outline" {...props}></Icon>
