<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3tgi9b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3tgi9b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freepbx-dark" {...props}></Icon>
