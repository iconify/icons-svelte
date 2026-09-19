<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mncjdgbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mncjdgbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cherish" {...props}></Icon>
