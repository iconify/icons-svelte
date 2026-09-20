<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma4ppccnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ma4ppccnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-square-court-with-ball" {...props}></Icon>
