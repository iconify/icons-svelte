<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz7-hy8bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gz7-hy8bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:fried-egg-breakfast-solid" {...props}></Icon>
