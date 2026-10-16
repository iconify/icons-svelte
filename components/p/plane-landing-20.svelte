<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyo6-384c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cyo6-384c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plane-landing-20" {...props}></Icon>
