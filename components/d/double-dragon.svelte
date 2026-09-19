<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in3r41qir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in3r41qir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:double-dragon" {...props}></Icon>
