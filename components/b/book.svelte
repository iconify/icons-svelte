<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3tbkh7zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3tbkh7zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:book" {...props}></Icon>
