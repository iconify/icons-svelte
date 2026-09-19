<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqu2my3vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xqu2my3vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:mask" {...props}></Icon>
