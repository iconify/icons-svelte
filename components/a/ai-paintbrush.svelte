<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwq8uec-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwq8uec-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-paintbrush" {...props}></Icon>
