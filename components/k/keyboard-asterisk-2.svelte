<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pned3bcjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pned3bcjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:keyboard-asterisk-2" {...props}></Icon>
