<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcr7icbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcr7icbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:play-bar-v-two-out" {...props}></Icon>
