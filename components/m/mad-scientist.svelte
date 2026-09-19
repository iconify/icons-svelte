<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxmka4bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxmka4bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mad-scientist" {...props}></Icon>
