<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcaj8rqjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcaj8rqjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:compass" {...props}></Icon>
