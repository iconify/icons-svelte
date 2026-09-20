<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi3ojut4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi3ojut4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cone" {...props}></Icon>
