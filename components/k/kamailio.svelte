<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsex8rb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsex8rb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kamailio" {...props}></Icon>
