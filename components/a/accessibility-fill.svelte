<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojx-05bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojx-05bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:accessibility-fill" {...props}></Icon>
