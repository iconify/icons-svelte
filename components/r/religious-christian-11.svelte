<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8wmx0buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="w8wmx0buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-christian-11" {...props}></Icon>
