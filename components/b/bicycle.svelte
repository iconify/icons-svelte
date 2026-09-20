<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye30ufs3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ye30ufs3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bicycle" {...props}></Icon>
