<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r59-vnb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r59-vnb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bot-off-fill" {...props}></Icon>
