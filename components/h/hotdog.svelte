<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mki0tacaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="mki0tacaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hotdog" {...props}></Icon>
