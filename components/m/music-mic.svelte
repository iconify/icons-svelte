<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu3blvvbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uu3blvvbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:music-mic" {...props}></Icon>
