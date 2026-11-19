<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hck1cab9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hck1cab9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:move" {...props}></Icon>
