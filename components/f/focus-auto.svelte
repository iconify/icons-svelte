<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek72wackg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek72wackg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:focus-auto" {...props}></Icon>
