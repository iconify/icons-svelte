<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5c_j2bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="c5c_j2bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:minus-square-o" {...props}></Icon>
