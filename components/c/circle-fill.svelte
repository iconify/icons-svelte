<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs7opybrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs7opybrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-fill" {...props}></Icon>
