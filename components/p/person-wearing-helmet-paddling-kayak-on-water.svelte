<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7pma5bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w7pma5bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-helmet-paddling-kayak-on-water" {...props}></Icon>
