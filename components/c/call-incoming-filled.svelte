<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iruu2iqcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iruu2iqcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:call-incoming-filled" {...props}></Icon>
