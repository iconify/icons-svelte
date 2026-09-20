<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ul88bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j7ul88bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:landing" {...props}></Icon>
