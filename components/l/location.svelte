<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3_f5bcdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j3_f5bcdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:location" {...props}></Icon>
