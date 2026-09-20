<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh16im3fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh16im3fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-2" {...props}></Icon>
