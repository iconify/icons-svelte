<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7p0n8gyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7p0n8gyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:elipse-frame" {...props}></Icon>
