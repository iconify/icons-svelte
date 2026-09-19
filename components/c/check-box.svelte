<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-fdedcse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":448};
const content = `<path class="d-fdedcse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:check-box" {...props}></Icon>
