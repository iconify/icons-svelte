<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyt-q6bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyt-q6bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:endpoints-disconnected" {...props}></Icon>
