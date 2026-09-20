<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyx3iwnif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyx3iwnif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:modern-tv-remote-smart-bold" {...props}></Icon>
