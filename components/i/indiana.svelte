<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb16_pbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kb16_pbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:indiana" {...props}></Icon>
