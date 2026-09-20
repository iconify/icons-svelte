<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/redq9pfak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="redq9pfak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-check" {...props}></Icon>
