<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo0r8nblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo0r8nblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:graduation-cap" {...props}></Icon>
