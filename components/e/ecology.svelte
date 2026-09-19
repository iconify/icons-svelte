<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqv9c1ert.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqv9c1ert"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ecology" {...props}></Icon>
