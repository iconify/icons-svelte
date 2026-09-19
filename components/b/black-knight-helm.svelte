<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngqy7dzmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ngqy7dzmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:black-knight-helm" {...props}></Icon>
