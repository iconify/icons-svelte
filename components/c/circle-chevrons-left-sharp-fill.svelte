<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvp-v1b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvp-v1b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevrons-left-sharp-fill" {...props}></Icon>
