<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv__j6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv__j6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:alarm" {...props}></Icon>
