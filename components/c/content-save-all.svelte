<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxkizf0gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxkizf0gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:content-save-all" {...props}></Icon>
