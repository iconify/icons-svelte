<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th3di3bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="th3di3bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:heavy-rain-filled" {...props}></Icon>
