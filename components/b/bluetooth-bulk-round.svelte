<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi2fi3bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi2fi3bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bluetooth-bulk-round" {...props}></Icon>
