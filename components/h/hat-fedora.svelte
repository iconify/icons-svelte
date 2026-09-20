<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcb6erbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcb6erbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hat-fedora" {...props}></Icon>
