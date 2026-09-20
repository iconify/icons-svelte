<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqmd109zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eqmd109zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:new-folder-flat" {...props}></Icon>
