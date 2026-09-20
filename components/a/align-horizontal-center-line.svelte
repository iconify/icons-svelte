<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u25n3tb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u25n3tb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-center-line" {...props}></Icon>
