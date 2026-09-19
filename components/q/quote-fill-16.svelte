<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7jzx_b7q.css';
import '../../css/r/rx4fkk1gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m7jzx_b7q"/><path class="rx4fkk1gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:quote-fill-16" {...props}></Icon>
