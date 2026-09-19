<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-tok76br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r-tok76br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-arrow-up-fill" {...props}></Icon>
