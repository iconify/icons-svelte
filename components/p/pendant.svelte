<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uviwnnbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uviwnnbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pendant" {...props}></Icon>
