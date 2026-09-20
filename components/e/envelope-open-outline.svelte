<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6nxtzqqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6nxtzqqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:envelope-open-outline" {...props}></Icon>
