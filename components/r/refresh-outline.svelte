<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oppifdcay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oppifdcay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:refresh-outline" {...props}></Icon>
