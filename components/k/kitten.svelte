<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0ts1q8ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v0ts1q8ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:kitten" {...props}></Icon>
