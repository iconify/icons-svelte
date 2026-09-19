<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj_clkr6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bj_clkr6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:arrows-expand" {...props}></Icon>
