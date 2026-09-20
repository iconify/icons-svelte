<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md_u1obyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md_u1obyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-waves-solid" {...props}></Icon>
