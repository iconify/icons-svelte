<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz9ys0aib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fz9ys0aib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eye-shield" {...props}></Icon>
