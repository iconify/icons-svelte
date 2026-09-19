<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8op9voft.css';
import '../../css/w/wckr9kb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8op9voft"/><path class="wckr9kb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-circle-up-outline" {...props}></Icon>
