<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0mu64ktm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0mu64ktm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:navigation-fill-round" {...props}></Icon>
