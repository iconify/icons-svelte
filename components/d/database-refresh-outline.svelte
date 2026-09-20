<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y862j7ftr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y862j7ftr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-refresh-outline" {...props}></Icon>
