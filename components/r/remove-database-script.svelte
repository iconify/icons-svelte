<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlngh0wix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlngh0wix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:remove-database-script" {...props}></Icon>
