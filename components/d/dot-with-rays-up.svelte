<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc6a_rusm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jc6a_rusm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dot-with-rays-up" {...props}></Icon>
