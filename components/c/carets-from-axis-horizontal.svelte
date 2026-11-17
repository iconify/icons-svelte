<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp839kwkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp839kwkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:carets-from-axis-horizontal" {...props}></Icon>
