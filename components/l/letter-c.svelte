<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v378jubmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v378jubmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-c" {...props}></Icon>
