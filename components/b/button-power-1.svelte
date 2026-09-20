<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9c5oyb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c9c5oyb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:button-power-1" {...props}></Icon>
