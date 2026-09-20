<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocurxub7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocurxub7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flip-horizontal-2-fill" {...props}></Icon>
