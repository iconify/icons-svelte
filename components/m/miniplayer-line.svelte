<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dszx4tb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dszx4tb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:miniplayer-line" {...props}></Icon>
