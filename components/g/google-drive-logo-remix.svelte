<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu14m29tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yu14m29tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:google-drive-logo-remix" {...props}></Icon>
