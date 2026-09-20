<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7-g323_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="n7-g323_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:ranger-station-11" {...props}></Icon>
