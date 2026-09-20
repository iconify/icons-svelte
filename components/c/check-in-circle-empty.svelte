<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsbipqluu.css';
import '../../css/m/m723m1bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lsbipqluu"/><path clip-rule="evenodd" class="m723m1bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:check-in-circle-empty" {...props}></Icon>
