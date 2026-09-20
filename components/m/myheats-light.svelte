<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxzqot-ta.css';
import '../../css/s/szpwprb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxzqot-ta"/><path class="szpwprb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:myheats-light" {...props}></Icon>
