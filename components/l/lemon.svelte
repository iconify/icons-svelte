<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc9ruyn8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jc9ruyn8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:lemon" {...props}></Icon>
