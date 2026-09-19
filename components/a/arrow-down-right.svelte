<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz6vqmbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dz6vqmbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:arrow-down-right" {...props}></Icon>
