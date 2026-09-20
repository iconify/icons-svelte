<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyo2u0bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyo2u0bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:recycle-1" {...props}></Icon>
