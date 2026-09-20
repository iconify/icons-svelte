<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjnhr6ifg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rjnhr6ifg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fire-alarm-2-solid" {...props}></Icon>
