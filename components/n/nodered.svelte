<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l30o51dbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l30o51dbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nodered" {...props}></Icon>
