<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8jv9db4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t8jv9db4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cliff-crossing" {...props}></Icon>
