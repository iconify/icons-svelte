<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjtpl_b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjtpl_b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:eye-snake-solid" {...props}></Icon>
