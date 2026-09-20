<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6aaq_a1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x6aaq_a1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:mobile-filled" {...props}></Icon>
