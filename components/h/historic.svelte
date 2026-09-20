<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygbst9bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ygbst9bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:historic" {...props}></Icon>
