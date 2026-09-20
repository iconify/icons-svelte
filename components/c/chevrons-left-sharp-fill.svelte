<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi1rvacfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1rvacfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-left-sharp-fill" {...props}></Icon>
