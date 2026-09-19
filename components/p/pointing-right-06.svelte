<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac5n8q2pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac5n8q2pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-right-06" {...props}></Icon>
