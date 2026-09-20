<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs-zgiblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs-zgiblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chat-line" {...props}></Icon>
