<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p274n3n9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p274n3n9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-outline" {...props}></Icon>
