<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frwz6gr7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frwz6gr7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bigbluebutton" {...props}></Icon>
