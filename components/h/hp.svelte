<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z97na1b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z97na1b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:hp" {...props}></Icon>
