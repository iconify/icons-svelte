<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0-41zb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0-41zb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:info-serif-box-outline" {...props}></Icon>
