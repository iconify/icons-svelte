<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgqg5hbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgqg5hbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:empty-recycle-bin-1-remix" {...props}></Icon>
