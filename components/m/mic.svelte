<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c96awj_av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c96awj_av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mic" {...props}></Icon>
