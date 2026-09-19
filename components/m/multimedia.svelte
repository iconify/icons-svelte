<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqcv_0rkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqcv_0rkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:multimedia" {...props}></Icon>
