<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yswnypbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yswnypbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:film-pause" {...props}></Icon>
