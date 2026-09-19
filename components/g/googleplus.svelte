<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz17u31mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="tz17u31mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:googleplus" {...props}></Icon>
