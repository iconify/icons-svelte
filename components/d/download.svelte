<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_zwrn1lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="j_zwrn1lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:download" {...props}></Icon>
