<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8-iphu6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8-iphu6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:apple-fill" {...props}></Icon>
