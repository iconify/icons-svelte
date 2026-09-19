<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it330lbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="it330lbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-item-1" {...props}></Icon>
