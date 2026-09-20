<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/synsbsj1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="synsbsj1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:castle-keep" {...props}></Icon>
