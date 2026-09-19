<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi4gs-b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qi4gs-b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:forward" {...props}></Icon>
