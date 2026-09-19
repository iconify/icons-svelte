<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tas0m7brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tas0m7brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:multiple-targets" {...props}></Icon>
