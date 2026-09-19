<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs733r24k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs733r24k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:action" {...props}></Icon>
