<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc58z1b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hc58z1b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:maryland" {...props}></Icon>
