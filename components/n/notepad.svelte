<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz93mysds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz93mysds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:notepad" {...props}></Icon>
