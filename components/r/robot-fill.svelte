<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3d5p9bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3d5p9bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:robot-fill" {...props}></Icon>
