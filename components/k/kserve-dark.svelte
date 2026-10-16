<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljw_3tj1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ljw_3tj1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kserve-dark" {...props}></Icon>
