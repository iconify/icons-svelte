<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpbc8_o4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hpbc8_o4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-13" {...props}></Icon>
