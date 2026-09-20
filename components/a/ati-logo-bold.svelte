<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwaanvb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwaanvb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ati-logo-bold" {...props}></Icon>
