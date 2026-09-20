<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyk9cabui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyk9cabui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:invisible-2" {...props}></Icon>
