<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf0au4b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf0au4b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:puzzle-bulk-round" {...props}></Icon>
