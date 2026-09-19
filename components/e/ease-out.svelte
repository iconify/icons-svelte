<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgcnw6b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgcnw6b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ease-out" {...props}></Icon>
