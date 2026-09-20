<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcr4y4byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lcr4y4byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pool-ladder-solid" {...props}></Icon>
