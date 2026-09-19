<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tug4wjebt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tug4wjebt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-circle-right" {...props}></Icon>
