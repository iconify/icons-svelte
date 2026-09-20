<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7ylwbb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7ylwbb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-line-fill" {...props}></Icon>
