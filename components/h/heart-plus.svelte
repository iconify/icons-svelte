<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in2f1jboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in2f1jboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-plus" {...props}></Icon>
