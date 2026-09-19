<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um9txejzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="um9txejzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:minus-square" {...props}></Icon>
