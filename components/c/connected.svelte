<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-d1pb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kb-d1pb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:connected" {...props}></Icon>
