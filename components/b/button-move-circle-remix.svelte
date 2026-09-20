<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d86ru6ydk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d86ru6ydk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:button-move-circle-remix" {...props}></Icon>
