<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fji8a4b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fji8a4b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:baggage-solid" {...props}></Icon>
