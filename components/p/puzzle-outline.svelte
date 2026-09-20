<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltmuz0bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltmuz0bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:puzzle-outline" {...props}></Icon>
