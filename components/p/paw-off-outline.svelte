<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp00hucjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp00hucjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paw-off-outline" {...props}></Icon>
