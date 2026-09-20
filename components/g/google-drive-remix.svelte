<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm43aowgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sm43aowgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:google-drive-remix" {...props}></Icon>
