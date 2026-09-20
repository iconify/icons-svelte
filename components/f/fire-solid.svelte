<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6_fz7-2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6_fz7-2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fire-solid" {...props}></Icon>
