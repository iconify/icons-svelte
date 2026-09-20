<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv6pjmbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv6pjmbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:navigation-menu-bold" {...props}></Icon>
