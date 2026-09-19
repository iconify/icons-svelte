<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw-jh6bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nw-jh6bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-top" {...props}></Icon>
