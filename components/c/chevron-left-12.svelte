<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtvtce9_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mtvtce9_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-left-12" {...props}></Icon>
