<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf097o-vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf097o-vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:mysql" {...props}></Icon>
