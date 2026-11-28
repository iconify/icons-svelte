<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2hkb1fev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2hkb1fev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:playlist-x" {...props}></Icon>
