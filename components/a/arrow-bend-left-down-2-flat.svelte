<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp_c66vkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hp_c66vkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-bend-left-down-2-flat" {...props}></Icon>
