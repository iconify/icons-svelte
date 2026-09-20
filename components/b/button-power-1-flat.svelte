<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0etbo8ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c0etbo8ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-power-1-flat" {...props}></Icon>
