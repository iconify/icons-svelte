<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmn2bxb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rmn2bxb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:expand-all" {...props}></Icon>
