<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5h0rrus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vc5h0rrus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:diamonds-symbol" {...props}></Icon>
