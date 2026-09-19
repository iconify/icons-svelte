<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l80e67qml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l80e67qml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mic-off-01" {...props}></Icon>
