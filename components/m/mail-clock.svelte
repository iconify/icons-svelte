<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xph50ihtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xph50ihtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-clock" {...props}></Icon>
