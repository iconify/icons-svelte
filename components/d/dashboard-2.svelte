<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc0wjpb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc0wjpb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-2" {...props}></Icon>
