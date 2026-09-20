<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0cs48b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0cs48b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-pin" {...props}></Icon>
