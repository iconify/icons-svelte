<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw5b5qa8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw5b5qa8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:china-railway-fill" {...props}></Icon>
