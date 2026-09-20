<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgr9lbbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sgr9lbbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bicycle-share" {...props}></Icon>
