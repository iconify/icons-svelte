<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbj0pbvta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbj0pbvta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clubs-fill" {...props}></Icon>
