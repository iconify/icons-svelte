<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjm9yabjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fjm9yabjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cardboard-box-closed" {...props}></Icon>
