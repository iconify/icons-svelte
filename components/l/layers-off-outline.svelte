<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss6ee4bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss6ee4bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:layers-off-outline" {...props}></Icon>
