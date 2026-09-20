<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqr4buhdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="oqr4buhdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:button-pause-circle" {...props}></Icon>
