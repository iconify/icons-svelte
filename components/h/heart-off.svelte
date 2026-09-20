<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb3ma9bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb3ma9bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heart-off" {...props}></Icon>
