<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrbt_q4og.css';
import '../../css/p/pt8e8sjhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrbt_q4og"/><path class="pt8e8sjhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:backspace-outline" {...props}></Icon>
