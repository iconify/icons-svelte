<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mim7gjbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mim7gjbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-filled" {...props}></Icon>
