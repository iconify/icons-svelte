<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eofb2ccfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eofb2ccfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:panzerfaust" {...props}></Icon>
