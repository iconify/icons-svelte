<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7pwbu_lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h7pwbu_lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:arrows-long-right" {...props}></Icon>
