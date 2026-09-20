<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbeh8kbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbeh8kbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dodopayments" {...props}></Icon>
