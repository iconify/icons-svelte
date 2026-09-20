<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-mp_qbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-mp_qbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:config" {...props}></Icon>
