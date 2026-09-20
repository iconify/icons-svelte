<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y--xh7bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y--xh7bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:calculator-1-remix" {...props}></Icon>
