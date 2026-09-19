<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-oj87b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="z-oj87b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:forward-alt" {...props}></Icon>
