<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgyr5-bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wgyr5-bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:axe" {...props}></Icon>
