<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqhdlkbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqhdlkbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-bluetooth-outline" {...props}></Icon>
