<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8l2z-7sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8l2z-7sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gamepad2-filled" {...props}></Icon>
