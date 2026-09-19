<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yub020v6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yub020v6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:ad" {...props}></Icon>
