<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5hzbmbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5hzbmbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edit-circle-line" {...props}></Icon>
