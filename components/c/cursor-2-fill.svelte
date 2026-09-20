<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_xa14bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_xa14bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-2-fill" {...props}></Icon>
