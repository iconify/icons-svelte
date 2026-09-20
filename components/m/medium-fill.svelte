<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml8f8msdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml8f8msdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:medium-fill" {...props}></Icon>
