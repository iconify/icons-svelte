<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytz6a3bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytz6a3bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:focus-field-horizontal" {...props}></Icon>
