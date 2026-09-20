<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufuuu7b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufuuu7b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:american-football-line" {...props}></Icon>
