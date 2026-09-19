<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6zmvbcdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="u6zmvbcdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:picasa" {...props}></Icon>
