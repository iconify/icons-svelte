<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvoxb-ghc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvoxb-ghc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layer-send-backward" {...props}></Icon>
