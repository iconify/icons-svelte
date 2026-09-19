<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg-sl6llt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mg-sl6llt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-merge" {...props}></Icon>
