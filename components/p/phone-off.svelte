<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxt2xwifj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxt2xwifj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:phone-off" {...props}></Icon>
