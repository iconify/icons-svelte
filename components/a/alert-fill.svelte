<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvrvn9blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvrvn9blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-fill" {...props}></Icon>
