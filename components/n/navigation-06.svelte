<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7qsv3bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7qsv3bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:navigation-06" {...props}></Icon>
