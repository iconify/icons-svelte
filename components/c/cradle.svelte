<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f086w4b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f086w4b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cradle" {...props}></Icon>
