<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo4parbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eo4parbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-right" {...props}></Icon>
