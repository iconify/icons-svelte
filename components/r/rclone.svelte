<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtt2647pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtt2647pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rclone" {...props}></Icon>
