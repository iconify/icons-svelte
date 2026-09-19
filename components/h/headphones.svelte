<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkrrltrgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mkrrltrgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:headphones" {...props}></Icon>
