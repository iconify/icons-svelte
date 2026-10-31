<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2jy7ccqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2jy7ccqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-5-fill-round" {...props}></Icon>
