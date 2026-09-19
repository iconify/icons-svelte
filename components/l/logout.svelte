<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6_snmbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":672};
const content = `<path class="t6_snmbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:logout" {...props}></Icon>
