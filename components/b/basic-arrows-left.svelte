<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbthg9fde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jbthg9fde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-left" {...props}></Icon>
