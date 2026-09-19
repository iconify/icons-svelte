<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox92i9e_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ox92i9e_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:refresh" {...props}></Icon>
