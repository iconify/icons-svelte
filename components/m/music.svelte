<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwg_h6bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="iwg_h6bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:music" {...props}></Icon>
