<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcfsm3qkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcfsm3qkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pump-off" {...props}></Icon>
