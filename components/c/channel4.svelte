<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl09u1b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl09u1b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:channel4" {...props}></Icon>
