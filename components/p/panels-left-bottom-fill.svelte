<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc5-p1byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc5-p1byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-left-bottom-fill" {...props}></Icon>
