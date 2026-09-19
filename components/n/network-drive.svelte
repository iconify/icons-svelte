<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcimb-b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcimb-b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:network-drive" {...props}></Icon>
