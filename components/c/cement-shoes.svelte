<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l86ufdcfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l86ufdcfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cement-shoes" {...props}></Icon>
