<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulkqwac8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulkqwac8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mountain-2-line" {...props}></Icon>
