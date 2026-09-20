<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu86w64jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wu86w64jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:oc-text-above-caption" {...props}></Icon>
