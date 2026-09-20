<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq8hgbwan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eq8hgbwan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picking-guidance-filled" {...props}></Icon>
