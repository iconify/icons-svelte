<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr_ur5bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xr_ur5bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:insomnia" {...props}></Icon>
