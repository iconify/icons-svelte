<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu-7yvbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu-7yvbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-column-big-sharp" {...props}></Icon>
