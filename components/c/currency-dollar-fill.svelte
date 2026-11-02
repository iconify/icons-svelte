<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkcw2bc9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkcw2bc9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-dollar-fill" {...props}></Icon>
