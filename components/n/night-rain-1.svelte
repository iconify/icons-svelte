<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avsdhy2ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avsdhy2ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:night-rain-1" {...props}></Icon>
