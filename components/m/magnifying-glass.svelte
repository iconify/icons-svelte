<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzdy0xb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzdy0xb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:magnifying-glass" {...props}></Icon>
