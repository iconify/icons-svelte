<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl4gu9brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl4gu9brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:desktop-alt-slash" {...props}></Icon>
