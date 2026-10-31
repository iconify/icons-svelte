<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epjuc8bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epjuc8bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paint-bucket-round" {...props}></Icon>
