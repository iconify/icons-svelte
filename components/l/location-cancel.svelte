<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4vjbob-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4vjbob-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-cancel" {...props}></Icon>
