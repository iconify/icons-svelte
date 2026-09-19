<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtg9cxbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vtg9cxbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:paperclip" {...props}></Icon>
