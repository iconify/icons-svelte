<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp2-434cc.css';
import '../../css/m/mzibl9poh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dp2-434cc"/><path class="mzibl9poh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:open" {...props}></Icon>
