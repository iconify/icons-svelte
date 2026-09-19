<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr-n4dbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tr-n4dbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-093" {...props}></Icon>
