<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0zncejna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0zncejna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-outline" {...props}></Icon>
