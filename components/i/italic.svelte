<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw689ii1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="sw689ii1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:italic" {...props}></Icon>
