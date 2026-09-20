<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxfgd9bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oxfgd9bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:music-tone-alt" {...props}></Icon>
