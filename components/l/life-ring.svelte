<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-19e_q6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e-19e_q6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:life-ring" {...props}></Icon>
