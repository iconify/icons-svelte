<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i68vwmyrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i68vwmyrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:minus-circle-solid" {...props}></Icon>
