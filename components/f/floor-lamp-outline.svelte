<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmn1gik9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmn1gik9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floor-lamp-outline" {...props}></Icon>
