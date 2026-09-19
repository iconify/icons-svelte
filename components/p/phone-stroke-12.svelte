<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgk69x2ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qgk69x2ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-stroke-12" {...props}></Icon>
