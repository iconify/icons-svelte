<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc3urnw9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tc3urnw9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mail-read" {...props}></Icon>
