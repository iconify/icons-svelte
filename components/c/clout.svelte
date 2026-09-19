<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk-zyny4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mk-zyny4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clout" {...props}></Icon>
