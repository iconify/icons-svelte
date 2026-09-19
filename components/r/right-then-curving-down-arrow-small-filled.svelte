<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdpb0ccux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sdpb0ccux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-then-curving-down-arrow-small-filled" {...props}></Icon>
