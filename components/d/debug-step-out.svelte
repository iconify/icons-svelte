<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib6l7jmqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ib6l7jmqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-step-out" {...props}></Icon>
