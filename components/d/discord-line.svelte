<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzp3mo5ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzp3mo5ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:discord-line" {...props}></Icon>
