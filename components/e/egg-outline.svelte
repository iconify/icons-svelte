<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clg852-dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clg852-dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:egg-outline" {...props}></Icon>
