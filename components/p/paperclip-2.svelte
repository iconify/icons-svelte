<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uci1gs-og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uci1gs-og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:paperclip-2" {...props}></Icon>
