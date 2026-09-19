<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo4-ahbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zo4-ahbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:herbs-bundle" {...props}></Icon>
