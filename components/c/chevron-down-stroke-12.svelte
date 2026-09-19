<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg3p3ab6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lg3p3ab6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-down-stroke-12" {...props}></Icon>
