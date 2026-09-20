<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wue5c4bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wue5c4bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:octagon" {...props}></Icon>
