<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiongsb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiongsb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:american-football-line" {...props}></Icon>
