<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw5h_935k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5h_935k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gamepad-buttons-filled" {...props}></Icon>
