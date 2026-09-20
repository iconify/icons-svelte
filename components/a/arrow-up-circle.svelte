<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ft6soej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ft6soej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrow-up-circle" {...props}></Icon>
