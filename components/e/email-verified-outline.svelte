<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoy593b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoy593b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-verified-outline" {...props}></Icon>
