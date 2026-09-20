<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux0t-4bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux0t-4bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ktor" {...props}></Icon>
