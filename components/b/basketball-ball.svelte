<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s90tjbc-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s90tjbc-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:basketball-ball" {...props}></Icon>
