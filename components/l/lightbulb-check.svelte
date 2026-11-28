<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbv90cc1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbv90cc1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:lightbulb-check" {...props}></Icon>
