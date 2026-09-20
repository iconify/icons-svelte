<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh8mkbcfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xh8mkbcfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:eraser-solid" {...props}></Icon>
