<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qor6go1jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qor6go1jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:game-console" {...props}></Icon>
