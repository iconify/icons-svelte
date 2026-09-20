<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8q0-j4-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u8q0-j4-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:forward-solid" {...props}></Icon>
