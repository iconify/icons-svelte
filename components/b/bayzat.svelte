<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8c01bogj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":23};
const content = `<path class="v8c01bogj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bayzat" {...props}></Icon>
