<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8z4a0azf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8z4a0azf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:nose-smell" {...props}></Icon>
