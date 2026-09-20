<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsb86qbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="wsb86qbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person" {...props}></Icon>
