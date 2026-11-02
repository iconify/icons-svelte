<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc0x6ebqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc0x6ebqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lamp-wall-down-fill" {...props}></Icon>
