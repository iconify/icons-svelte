<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcv8ny-rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wcv8ny-rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-down-left-solid" {...props}></Icon>
