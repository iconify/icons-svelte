<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s59g9_0ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s59g9_0ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:move" {...props}></Icon>
