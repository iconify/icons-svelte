<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp49s3s_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp49s3s_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:folder" {...props}></Icon>
