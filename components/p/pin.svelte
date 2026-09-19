<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-hafv83m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-hafv83m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:pin" {...props}></Icon>
