<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6p9v1bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j6p9v1bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:bank-card" {...props}></Icon>
