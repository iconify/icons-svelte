<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys-ja_bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ys-ja_bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bell-notification-remix" {...props}></Icon>
