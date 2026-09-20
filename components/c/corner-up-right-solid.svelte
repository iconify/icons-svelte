<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgsz4nbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wgsz4nbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-up-right-solid" {...props}></Icon>
