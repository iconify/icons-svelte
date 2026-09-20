<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj-jz8bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xj-jz8bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:login-1-remix" {...props}></Icon>
