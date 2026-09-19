<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq2d5abyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq2d5abyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:optimize" {...props}></Icon>
