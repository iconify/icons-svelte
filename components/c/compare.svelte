<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dum2n6gev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dum2n6gev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:compare" {...props}></Icon>
