<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxf8dlbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf8dlbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:plan" {...props}></Icon>
