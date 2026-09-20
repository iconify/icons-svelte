<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeu56e2ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeu56e2ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant" {...props}></Icon>
