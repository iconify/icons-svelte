<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mec9bobet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mec9bobet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-heart-fill" {...props}></Icon>
