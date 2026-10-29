<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl-c-h5mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl-c-h5mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:megaphone-solid" {...props}></Icon>
