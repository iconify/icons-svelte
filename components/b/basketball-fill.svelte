<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc54xowtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc54xowtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:basketball-fill" {...props}></Icon>
