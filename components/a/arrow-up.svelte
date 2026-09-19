<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afwu872mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afwu872mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-up" {...props}></Icon>
