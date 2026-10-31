<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obrt96bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obrt96bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:move-vertical-bulk-round" {...props}></Icon>
