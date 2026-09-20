<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3dqu4bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3dqu4bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:luanti" {...props}></Icon>
