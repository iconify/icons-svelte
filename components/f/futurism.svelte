<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3df32ggd.css';
import '../../css/r/rsbp7epmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3df32ggd"/><path class="rsbp7epmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:futurism" {...props}></Icon>
