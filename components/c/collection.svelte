<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8f0fw_qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g8f0fw_qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:collection" {...props}></Icon>
