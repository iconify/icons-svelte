<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig391mlei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ig391mlei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-cursor-2-solid" {...props}></Icon>
