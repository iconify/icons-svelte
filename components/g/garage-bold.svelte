<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvtmssb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvtmssb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:garage-bold" {...props}></Icon>
