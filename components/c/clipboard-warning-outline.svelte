<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-ksqghyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-ksqghyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-warning-outline" {...props}></Icon>
