<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ydx-euj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o5ydx-euj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flash-2-solid" {...props}></Icon>
