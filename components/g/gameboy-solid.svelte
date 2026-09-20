<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/troogcbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="troogcbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gameboy-solid" {...props}></Icon>
