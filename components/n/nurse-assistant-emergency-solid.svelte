<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4pi53b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c4pi53b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:nurse-assistant-emergency-solid" {...props}></Icon>
