<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaaimuocw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qaaimuocw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:minimize-window-2-solid" {...props}></Icon>
