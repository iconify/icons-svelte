<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu4mllbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu4mllbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:add" {...props}></Icon>
