<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss38_lbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ss38_lbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:magnifying-glass-plus" {...props}></Icon>
