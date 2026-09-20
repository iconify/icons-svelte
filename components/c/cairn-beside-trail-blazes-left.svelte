<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yksgd-bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yksgd-bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cairn-beside-trail-blazes-left" {...props}></Icon>
