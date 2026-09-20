<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4e2thb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4e2thb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-dollar-line" {...props}></Icon>
