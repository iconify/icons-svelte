<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwa9eacvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dwa9eacvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowshape-turn-up-left-circle" {...props}></Icon>
