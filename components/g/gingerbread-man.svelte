<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0w1066od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0w1066od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gingerbread-man" {...props}></Icon>
