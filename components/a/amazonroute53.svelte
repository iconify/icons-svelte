<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlph9yu2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlph9yu2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonroute53" {...props}></Icon>
