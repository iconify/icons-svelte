<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0z7iwm1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0z7iwm1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:corner-left-up" {...props}></Icon>
