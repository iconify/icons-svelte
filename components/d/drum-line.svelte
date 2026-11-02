<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdn7-dr4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdn7-dr4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drum-line" {...props}></Icon>
