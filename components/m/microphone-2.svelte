<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cegur4clo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cegur4clo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:microphone-2" {...props}></Icon>
