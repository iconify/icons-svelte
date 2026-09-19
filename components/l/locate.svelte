<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-g6vhizt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-g6vhizt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:locate" {...props}></Icon>
