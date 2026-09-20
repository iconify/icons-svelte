<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syeeeyb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path clip-rule="evenodd" class="syeeeyb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dub-dark" {...props}></Icon>
