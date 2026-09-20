<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a84g-42ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a84g-42ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-gas-station" {...props}></Icon>
