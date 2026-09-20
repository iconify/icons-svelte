<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqd_v-g0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jqd_v-g0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:beanie" {...props}></Icon>
