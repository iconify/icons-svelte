<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlzqg2b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlzqg2b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-check-outline" {...props}></Icon>
