<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_kutkb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="b_kutkb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:hearing-assistance" {...props}></Icon>
