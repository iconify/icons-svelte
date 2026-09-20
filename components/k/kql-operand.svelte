<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsx4-tbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dsx4-tbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:kql-operand" {...props}></Icon>
