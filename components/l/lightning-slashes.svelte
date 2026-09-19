<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9z6qm4bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9z6qm4bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-slashes" {...props}></Icon>
