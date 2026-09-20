<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu23s0b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu23s0b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:foundryvirtualtabletop" {...props}></Icon>
