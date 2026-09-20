<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fksw118oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fksw118oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:black-candy-light" {...props}></Icon>
