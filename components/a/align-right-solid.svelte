<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7m-1z1xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q7m-1z1xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-right-solid" {...props}></Icon>
