<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iks4w9psj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iks4w9psj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:middle-finger-fill" {...props}></Icon>
