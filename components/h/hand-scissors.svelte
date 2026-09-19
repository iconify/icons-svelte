<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp-_iwjua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pp-_iwjua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hand-scissors" {...props}></Icon>
