<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar0c3_b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar0c3_b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:check" {...props}></Icon>
