<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_-i05dah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="g_-i05dah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:github-square" {...props}></Icon>
