<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aav1k0baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aav1k0baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:play-hexagon-solid" {...props}></Icon>
