<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waa-_0dyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waa-_0dyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:button-rounded-filled" {...props}></Icon>
