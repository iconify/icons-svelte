<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6w_a129j.css';
import '../../css/z/zsup6ib6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p6w_a129j"/><path class="zsup6ib6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-bubble-oval-notification-solid" {...props}></Icon>
