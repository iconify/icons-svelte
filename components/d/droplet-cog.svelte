<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu943_v5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu943_v5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-cog" {...props}></Icon>
