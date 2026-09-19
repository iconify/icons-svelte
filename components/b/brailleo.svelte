<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgm8q8b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="vgm8q8b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailleo" {...props}></Icon>
