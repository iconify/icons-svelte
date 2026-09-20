<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asc-prbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asc-prbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edit-box-line" {...props}></Icon>
