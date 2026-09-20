<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns9o89kkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns9o89kkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:corn" {...props}></Icon>
