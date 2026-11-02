<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6dzgnbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6dzgnbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-up-left-fill" {...props}></Icon>
