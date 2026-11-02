<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de39s79xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de39s79xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:riding-fill" {...props}></Icon>
