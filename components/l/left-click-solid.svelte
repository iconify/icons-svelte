<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz0rwkzja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mz0rwkzja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:left-click-solid" {...props}></Icon>
