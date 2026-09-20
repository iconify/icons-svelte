<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqwsaac0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqwsaac0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:husd" {...props}></Icon>
