<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i73vyxe7x.css';
import '../../css/j/jdksqj83p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i73vyxe7x"/><path class="jdksqj83p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crow-ci-light" {...props}></Icon>
