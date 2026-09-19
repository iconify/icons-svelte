<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w148np-hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w148np-hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:chess-bishop" {...props}></Icon>
