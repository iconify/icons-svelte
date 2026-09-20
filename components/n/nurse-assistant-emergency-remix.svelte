<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu4ad0blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cu4ad0blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:nurse-assistant-emergency-remix" {...props}></Icon>
