<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxo1xc58t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oxo1xc58t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-left-circle" {...props}></Icon>
