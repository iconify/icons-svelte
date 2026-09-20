<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi7fkehyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi7fkehyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-clock-outline" {...props}></Icon>
