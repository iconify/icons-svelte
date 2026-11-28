<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr99_emqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jr99_emqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:copy-check-bold" {...props}></Icon>
