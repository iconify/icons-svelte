<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1od4ibpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1od4ibpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:google-drive-warning" {...props}></Icon>
