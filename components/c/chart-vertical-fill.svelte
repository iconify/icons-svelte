<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo8y5cbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo8y5cbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-vertical-fill" {...props}></Icon>
