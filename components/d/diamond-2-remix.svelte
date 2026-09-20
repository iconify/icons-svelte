<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7jhx31iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m7jhx31iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:diamond-2-remix" {...props}></Icon>
