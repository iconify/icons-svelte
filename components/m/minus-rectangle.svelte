<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbf5ltb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mbf5ltb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:minus-rectangle" {...props}></Icon>
