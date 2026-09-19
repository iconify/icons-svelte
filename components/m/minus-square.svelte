<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/damadsbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="damadsbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:minus-square" {...props}></Icon>
