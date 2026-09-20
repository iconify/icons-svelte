<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h07tfzb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h07tfzb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bluetooth-disabled" {...props}></Icon>
