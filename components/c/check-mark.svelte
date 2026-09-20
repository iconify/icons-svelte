<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otrl-6b3q.css';
import '../../css/o/oq8tqccjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="otrl-6b3q"/><path class="oq8tqccjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:check-mark" {...props}></Icon>
