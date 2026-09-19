<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va-qs_okh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="va-qs_okh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:alarm-clock" {...props}></Icon>
