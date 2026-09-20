<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mziu1o0cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mziu1o0cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bicycle-bike-remix" {...props}></Icon>
