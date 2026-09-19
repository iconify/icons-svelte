<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jamt8gbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jamt8gbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:archive-fill" {...props}></Icon>
