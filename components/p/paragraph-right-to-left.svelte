<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwuzo1b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwuzo1b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:paragraph-right-to-left" {...props}></Icon>
