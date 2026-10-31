<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iln4uew0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iln4uew0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hammer-round" {...props}></Icon>
