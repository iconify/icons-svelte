<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv99-xynx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv99-xynx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:revenuecat" {...props}></Icon>
