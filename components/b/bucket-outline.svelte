<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4w9i_p-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4w9i_p-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bucket-outline" {...props}></Icon>
