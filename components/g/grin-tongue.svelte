<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkga0ac_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="jkga0ac_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-tongue" {...props}></Icon>
