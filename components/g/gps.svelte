<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvb9twb3e.css';
import '../../css/q/q0sfd_b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvb9twb3e"/><path class="q0sfd_b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:gps" {...props}></Icon>
