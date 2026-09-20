<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueo59ebwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueo59ebwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-list-3-line" {...props}></Icon>
