<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms-tfosij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms-tfosij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:old-lantern" {...props}></Icon>
