<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghed69pzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghed69pzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:luogu" {...props}></Icon>
