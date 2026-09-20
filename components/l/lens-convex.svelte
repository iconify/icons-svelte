<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn3wd3bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn3wd3bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:lens-convex" {...props}></Icon>
