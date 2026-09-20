<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck12p5bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck12p5bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-09-sort-ascending-fill" {...props}></Icon>
