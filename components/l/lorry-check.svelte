<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj66bgbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj66bgbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lorry-check" {...props}></Icon>
