<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouz__9e9k.css';
import '../../css/c/ctz427bry.css';
import '../../css/v/vkt-pxbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ouz__9e9k"/><path class="ctz427bry"/><path class="vkt-pxbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:layers" {...props}></Icon>
