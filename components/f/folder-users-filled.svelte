<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpcwsfbtq.css';
import '../../css/x/xv4mh2pto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpcwsfbtq"/><path class="xv4mh2pto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-users-filled" {...props}></Icon>
