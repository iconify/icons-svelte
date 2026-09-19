<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_34pvbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_34pvbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:fan" {...props}></Icon>
