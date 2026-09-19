<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aez2ipb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="aez2ipb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-ltr-stroke-12" {...props}></Icon>
