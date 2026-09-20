<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wto57b17c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="wto57b17c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:danger-11" {...props}></Icon>
