<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvjr2x3go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvjr2x3go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gamepad-filled" {...props}></Icon>
