<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woe447n8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="woe447n8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hard-drive-1-remix" {...props}></Icon>
