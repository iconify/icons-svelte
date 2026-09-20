<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrlv65jph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lrlv65jph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:attachments-outline" {...props}></Icon>
