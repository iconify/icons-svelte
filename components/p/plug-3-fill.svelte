<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufpbpac8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufpbpac8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:plug-3-fill" {...props}></Icon>
