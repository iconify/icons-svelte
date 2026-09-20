<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f21smdbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f21smdbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ai-scanner-robot-remix" {...props}></Icon>
