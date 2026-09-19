<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_9z6yunr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_9z6yunr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:package" {...props}></Icon>
