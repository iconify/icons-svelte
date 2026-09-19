<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjc8aza2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjc8aza2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pyramid-structure-01" {...props}></Icon>
