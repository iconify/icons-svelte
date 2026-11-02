<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn6bvd5qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn6bvd5qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egg-crack-fill" {...props}></Icon>
