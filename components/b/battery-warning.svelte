<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab65ey4uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab65ey4uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:battery-warning" {...props}></Icon>
