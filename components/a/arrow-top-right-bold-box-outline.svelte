<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkw6s9bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkw6s9bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-right-bold-box-outline" {...props}></Icon>
