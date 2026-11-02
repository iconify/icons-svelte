<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u63w3k6_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u63w3k6_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:escalator-down-fill" {...props}></Icon>
