<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck8nk4b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck8nk4b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:inbox-archive-solid" {...props}></Icon>
