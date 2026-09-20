<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-9pnabwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-9pnabwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:champagne-line" {...props}></Icon>
