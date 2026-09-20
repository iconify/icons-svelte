<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p50x5tbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p50x5tbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-1-solid" {...props}></Icon>
