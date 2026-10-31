<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig5b-xtid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5b-xtid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:megaphone-fill-round" {...props}></Icon>
