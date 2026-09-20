<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9_6kjtky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9_6kjtky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-solid" {...props}></Icon>
