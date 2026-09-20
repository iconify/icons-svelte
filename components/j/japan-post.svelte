<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7a86-bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l7a86-bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-post" {...props}></Icon>
