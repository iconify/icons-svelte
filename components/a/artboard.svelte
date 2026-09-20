<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frt7vtf9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frt7vtf9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:artboard" {...props}></Icon>
