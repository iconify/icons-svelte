<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j72iiybcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j72iiybcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pretty-fangs" {...props}></Icon>
