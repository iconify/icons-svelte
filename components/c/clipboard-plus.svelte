<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs2-47bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs2-47bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-plus" {...props}></Icon>
