<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gifyl0-oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gifyl0-oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:one-eyed" {...props}></Icon>
