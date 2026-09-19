<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkxh5bcsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkxh5bcsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:paperclip" {...props}></Icon>
