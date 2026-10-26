<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk33ibcgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bk33ibcgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kserve" {...props}></Icon>
