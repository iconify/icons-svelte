<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dszkiqsya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dszkiqsya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:f-clef" {...props}></Icon>
