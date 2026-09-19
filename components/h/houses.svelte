<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_r4fnbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o_r4fnbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:houses" {...props}></Icon>
