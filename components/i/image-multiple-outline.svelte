<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrp-v4bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrp-v4bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-multiple-outline" {...props}></Icon>
