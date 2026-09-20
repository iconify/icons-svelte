<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_5-j-2ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_5-j-2ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kuma" {...props}></Icon>
