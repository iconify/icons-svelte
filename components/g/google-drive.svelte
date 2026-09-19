<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abtk0lbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abtk0lbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:google-drive" {...props}></Icon>
