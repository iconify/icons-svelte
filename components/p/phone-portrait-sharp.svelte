<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgn4__dfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgn4__dfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:phone-portrait-sharp" {...props}></Icon>
