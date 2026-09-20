<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6jeosdpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6jeosdpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coffee-maker-done" {...props}></Icon>
