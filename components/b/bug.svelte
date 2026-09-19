<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jofnmtrzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1600,"height":1568};
const content = `<path class="jofnmtrzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bug" {...props}></Icon>
