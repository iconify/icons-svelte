<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_ozp5bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s_ozp5bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:move" {...props}></Icon>
