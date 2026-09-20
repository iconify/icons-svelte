<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i25nmhjnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i25nmhjnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-indent-left-alignment-align-indent-paragraph-formatting-left-text" {...props}></Icon>
