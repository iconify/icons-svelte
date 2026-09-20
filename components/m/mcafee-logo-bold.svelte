<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6m20abim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6m20abim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:mcafee-logo-bold" {...props}></Icon>
