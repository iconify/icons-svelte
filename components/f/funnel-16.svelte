<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg_qtrbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lg_qtrbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:funnel-16" {...props}></Icon>
