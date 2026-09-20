<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1s00mbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o1s00mbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-charging-solid" {...props}></Icon>
