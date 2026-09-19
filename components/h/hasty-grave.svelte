<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w07ny-qpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w07ny-qpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hasty-grave" {...props}></Icon>
