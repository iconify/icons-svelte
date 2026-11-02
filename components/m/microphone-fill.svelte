<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgx1k0bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgx1k0bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:microphone-fill" {...props}></Icon>
