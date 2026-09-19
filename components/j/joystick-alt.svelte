<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df-f6gk1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df-f6gk1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:joystick-alt" {...props}></Icon>
