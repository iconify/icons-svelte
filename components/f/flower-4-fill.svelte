<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1i-prnbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1i-prnbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-4-fill" {...props}></Icon>
