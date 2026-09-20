<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pahc-5tby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pahc-5tby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dices-entertainment-gaming-dices-solid" {...props}></Icon>
