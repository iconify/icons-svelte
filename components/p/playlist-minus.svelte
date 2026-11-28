<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atyyepbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atyyepbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:playlist-minus" {...props}></Icon>
