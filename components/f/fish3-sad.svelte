<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecg4d0bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ecg4d0bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish3-sad" {...props}></Icon>
