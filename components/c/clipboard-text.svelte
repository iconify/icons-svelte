<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isyff-8qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isyff-8qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:clipboard-text" {...props}></Icon>
