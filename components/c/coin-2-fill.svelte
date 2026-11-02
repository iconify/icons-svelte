<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah6_ogb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah6_ogb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coin-2-fill" {...props}></Icon>
