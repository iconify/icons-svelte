<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfbmvaczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfbmvaczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flower-duotone" {...props}></Icon>
