<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7vp5_gqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7vp5_gqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:flash-timer-solid" {...props}></Icon>
