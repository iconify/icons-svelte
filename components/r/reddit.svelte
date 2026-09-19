<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9s_yp61w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9s_yp61w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:reddit" {...props}></Icon>
