<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfn4tbjty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfn4tbjty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:replit" {...props}></Icon>
