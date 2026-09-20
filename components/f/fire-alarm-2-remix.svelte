<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgmfd2b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vgmfd2b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fire-alarm-2-remix" {...props}></Icon>
