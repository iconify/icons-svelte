<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6uu00ymn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6uu00ymn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:battery-empty-2" {...props}></Icon>
