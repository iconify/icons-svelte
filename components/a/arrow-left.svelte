<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8g-31b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8g-31b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-left" {...props}></Icon>
