<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egk1a_o_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="egk1a_o_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-remove" {...props}></Icon>
