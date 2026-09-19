<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u87yr5b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="u87yr5b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:archive" {...props}></Icon>
