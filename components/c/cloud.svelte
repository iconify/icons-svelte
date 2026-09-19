<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_12i_b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o_12i_b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cloud" {...props}></Icon>
