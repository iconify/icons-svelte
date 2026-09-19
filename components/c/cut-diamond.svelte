<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar-8itt_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ar-8itt_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cut-diamond" {...props}></Icon>
