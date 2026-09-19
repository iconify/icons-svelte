<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-1tko0hh.css';
import '../../css/i/itcix3b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h-1tko0hh"/><path class="itcix3b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:layers-outline" {...props}></Icon>
