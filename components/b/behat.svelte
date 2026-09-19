<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw_m9ijfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":385,"height":512};
const content = `<path class="dw_m9ijfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:behat" {...props}></Icon>
