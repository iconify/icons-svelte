<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8t6yabiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8t6yabiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:quote-down-filled" {...props}></Icon>
