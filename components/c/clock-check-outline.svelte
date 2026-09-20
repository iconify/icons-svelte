<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzdjojyeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzdjojyeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-check-outline" {...props}></Icon>
