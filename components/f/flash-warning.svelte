<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d20g__sew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d20g__sew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:flash-warning" {...props}></Icon>
