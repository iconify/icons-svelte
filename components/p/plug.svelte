<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xikr_996s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xikr_996s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:plug" {...props}></Icon>
