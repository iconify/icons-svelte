<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkyuc8boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkyuc8boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:passport" {...props}></Icon>
