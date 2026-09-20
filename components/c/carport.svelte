<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytm_8fbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ytm_8fbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:carport" {...props}></Icon>
