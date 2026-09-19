<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3j4zebqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3j4zebqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:corner-up-left-fill" {...props}></Icon>
