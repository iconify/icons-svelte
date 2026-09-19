<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx0fi0t2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx0fi0t2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:central-shaheed-minar" {...props}></Icon>
