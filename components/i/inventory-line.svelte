<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt4y3362k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt4y3362k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inventory-line" {...props}></Icon>
