<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mckg81b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mckg81b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-left" {...props}></Icon>
