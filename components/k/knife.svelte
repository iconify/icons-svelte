<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp8_idbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cp8_idbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:knife" {...props}></Icon>
