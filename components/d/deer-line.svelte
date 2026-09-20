<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn30pmbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn30pmbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:deer-line" {...props}></Icon>
