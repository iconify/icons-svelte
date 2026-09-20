<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymix36bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymix36bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:glasses" {...props}></Icon>
