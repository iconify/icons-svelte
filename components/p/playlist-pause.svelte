<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyb7pnbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyb7pnbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:playlist-pause" {...props}></Icon>
