<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1pbxe94o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1pbxe94o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bowl" {...props}></Icon>
