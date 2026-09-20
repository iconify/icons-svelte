<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpgmlzb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpgmlzb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ink" {...props}></Icon>
