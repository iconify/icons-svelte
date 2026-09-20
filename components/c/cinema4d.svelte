<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzwz08yhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzwz08yhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cinema4d" {...props}></Icon>
