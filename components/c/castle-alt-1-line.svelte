<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8cpwltgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8cpwltgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:castle-alt-1-line" {...props}></Icon>
