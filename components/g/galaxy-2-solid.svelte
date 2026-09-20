<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk58jbbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xk58jbbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:galaxy-2-solid" {...props}></Icon>
