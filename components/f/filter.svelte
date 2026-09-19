<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2kh23b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="v2kh23b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:filter" {...props}></Icon>
