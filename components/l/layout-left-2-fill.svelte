<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epg42eebu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epg42eebu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-left-2-fill" {...props}></Icon>
