<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7n010b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7n010b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:oracle" {...props}></Icon>
