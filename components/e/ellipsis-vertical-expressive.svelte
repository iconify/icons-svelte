<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mawlj7b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mawlj7b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:ellipsis-vertical-expressive" {...props}></Icon>
