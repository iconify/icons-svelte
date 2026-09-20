<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a60lilr8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a60lilr8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-shield-line" {...props}></Icon>
