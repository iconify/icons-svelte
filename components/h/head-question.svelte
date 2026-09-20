<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcae4gsqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcae4gsqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-question" {...props}></Icon>
