<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a17q4j8vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a17q4j8vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bullet-impacts" {...props}></Icon>
